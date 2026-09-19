<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzrd1icfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="kzrd1icfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:mask-1" {...props}></Icon>
