<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ued2yndek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ued2yndek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:cross-hair-2" {...props}></Icon>
