<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkzaq9b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="rkzaq9b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:desktop" {...props}></Icon>
