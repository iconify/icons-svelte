<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm_beh2el.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="nm_beh2el"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:pause" {...props}></Icon>
