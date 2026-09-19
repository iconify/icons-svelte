<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9usbuzrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w9usbuzrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bookmark-fill-16" {...props}></Icon>
