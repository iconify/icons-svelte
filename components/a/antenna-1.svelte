<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9k_ldbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="g9k_ldbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:antenna-1" {...props}></Icon>
