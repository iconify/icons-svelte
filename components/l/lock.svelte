<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4n87sb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="w4n87sb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:lock" {...props}></Icon>
