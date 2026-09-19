<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iy43hrxgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="iy43hrxgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:n" {...props}></Icon>
