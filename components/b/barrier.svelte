<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztr00xb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ztr00xb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:barrier" {...props}></Icon>
