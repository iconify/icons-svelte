<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/y/y_9s_-bnx.css';
import '../../css/d/dza1onb6k.css';
import '../../css/x/xy9o4mbiz.css';
import '../../css/o/o7h2koe1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y_9s_-bnx"/><path class="dza1onb6k"/><path class="xy9o4mbiz"/><path class="o7h2koe1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-snowfall-linear" {...props}></Icon>
