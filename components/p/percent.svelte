<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrnvq_big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="qrnvq_big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:percent" {...props}></Icon>
