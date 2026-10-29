<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mdvkx-geo.css';
import '../../css/u/uxz8njb2w.css';
import '../../css/i/i-oq5ub8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mdvkx-geo"/><path class="uxz8njb2w"/><path class="i-oq5ub8f wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-bear" {...props}></Icon>
