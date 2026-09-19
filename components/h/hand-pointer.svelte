<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqromeb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nqromeb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-pointer" {...props}></Icon>
