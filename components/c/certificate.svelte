<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/clwivwvku.css';
import '../../css/w/w09xprbay.css';
import '../../css/w/wtll6dz5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="clwivwvku"/><path class="w09xprbay wm-a"/><path class="wm-a wtll6dz5m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:certificate" {...props}></Icon>
