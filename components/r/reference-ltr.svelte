<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d74gefb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d74gefb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:reference-ltr" {...props}></Icon>
