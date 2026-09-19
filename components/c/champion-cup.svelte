<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqq00-9sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="eqq00-9sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:champion-cup" {...props}></Icon>
