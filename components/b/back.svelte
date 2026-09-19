<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzaw-obto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="mzaw-obto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:back" {...props}></Icon>
