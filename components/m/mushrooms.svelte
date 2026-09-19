<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih-vw5bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="ih-vw5bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:mushrooms" {...props}></Icon>
