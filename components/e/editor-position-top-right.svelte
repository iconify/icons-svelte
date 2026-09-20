<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfhyygb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gfhyygb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-position-top-right" {...props}></Icon>
