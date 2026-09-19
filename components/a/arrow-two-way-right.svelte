<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovl0b1-lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ovl0b1-lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-two-way-right" {...props}></Icon>
