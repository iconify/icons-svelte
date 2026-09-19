<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7vuirbjs.css';
import '../../css/p/p3gjzeb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i7vuirbjs"/><path class="p3gjzeb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:new-window-fill-16" {...props}></Icon>
