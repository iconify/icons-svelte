<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9i8cmbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="i9i8cmbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-triangle-recycle" {...props}></Icon>
