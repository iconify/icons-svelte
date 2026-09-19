<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isade3bkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="isade3bkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:equals" {...props}></Icon>
