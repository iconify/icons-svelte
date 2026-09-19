<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr-wldb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="pr-wldb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:regular-shape" {...props}></Icon>
