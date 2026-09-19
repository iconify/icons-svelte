<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nluxihncq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nluxihncq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:angle-2" {...props}></Icon>
