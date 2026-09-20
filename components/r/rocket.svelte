<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1p9_wptb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p1p9_wptb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:rocket" {...props}></Icon>
