<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6lsvzbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="i6lsvzbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:flower-pot" {...props}></Icon>
