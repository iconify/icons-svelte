<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba_3aab4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ba_3aab4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:chair-1" {...props}></Icon>
