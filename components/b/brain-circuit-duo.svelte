<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ef3pdbyer.css';
import '../../css/f/f2-2wdbln.css';
import '../../css/b/be9_y4xan.css';
import '../../css/j/jlp-ovbkm.css';
import '../../css/r/rsulyv1ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ef3pdbyer"/><path class="f2-2wdbln wm-a"/><path class="be9_y4xan wm-a"/><path class="jlp-ovbkm"/><path class="rsulyv1ts wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:brain-circuit-duo" {...props}></Icon>
