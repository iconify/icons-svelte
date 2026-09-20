<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-o-c1b4o.css';
import '../../css/x/xd2ndxbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p-o-c1b4o"/><path class="xd2ndxbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-loading-50-percent-1" {...props}></Icon>
