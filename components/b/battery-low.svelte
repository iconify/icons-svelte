<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/e/e8mb1rodb.css';
import '../../css/e/e066grb0j.css';
import '../../css/h/hn7xqebqj.css';
import '../../css/w/w6r4lacra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="e8mb1rodb wm-shadow"/><path class="e066grb0j"/><path class="hn7xqebqj"/><path class="w6r4lacra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-retro:battery-low" {...props}></Icon>
