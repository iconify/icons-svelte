<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f7raeib7y.css';
import '../../css/p/plgg98bdj.css';
import '../../css/i/i-oq5ub8f.css';
import '../../css/m/mdvkx-geo.css';
import '../../css/u/uxz8njb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f7raeib7y"/><path class="plgg98bdj"/><path class="i-oq5ub8f wm-a"/><path class="mdvkx-geo"/><path class="uxz8njb2w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-bear-duo" {...props}></Icon>
