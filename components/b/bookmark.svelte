<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnr0-ylgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="nnr0-ylgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bookmark" {...props}></Icon>
