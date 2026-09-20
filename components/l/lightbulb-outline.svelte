<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz-r18bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hz-r18bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:lightbulb-outline" {...props}></Icon>
