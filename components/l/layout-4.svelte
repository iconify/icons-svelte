<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2-2p5bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="r2-2p5bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:layout-4" {...props}></Icon>
