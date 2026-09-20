<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq1qi5b_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oq1qi5b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:dry" {...props}></Icon>
