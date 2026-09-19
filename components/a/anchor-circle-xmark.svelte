<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbrj70bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="vbrj70bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:anchor-circle-xmark" {...props}></Icon>
