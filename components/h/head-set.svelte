<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpu81hs1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="dpu81hs1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:head-set" {...props}></Icon>
