<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s392k2bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s392k2bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:hammer-and-wrench" {...props}></Icon>
