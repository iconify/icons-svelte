<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxi_hacdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="hxi_hacdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:board" {...props}></Icon>
