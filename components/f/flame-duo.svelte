<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fvhj1mbod.css';
import '../../css/b/bmlr6ob0i.css';
import '../../css/l/lb5z5tb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fvhj1mbod"/><path class="bmlr6ob0i wm-a"/><path class="lb5z5tb2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flame-duo" {...props}></Icon>
