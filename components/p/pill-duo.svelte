<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bb_du2bxr.css';
import '../../css/e/ewn913uqn.css';
import '../../css/t/tph8vb83n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bb_du2bxr"/><path class="ewn913uqn wm-a"/><path class="tph8vb83n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:pill-duo" {...props}></Icon>
