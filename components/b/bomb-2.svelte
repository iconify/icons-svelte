<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wip14ubiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="wip14ubiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bomb-2" {...props}></Icon>
