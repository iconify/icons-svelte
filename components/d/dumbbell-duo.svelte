<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-sz2z30j.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/a43ax-bga.css';
import '../../css/r/rmoaf9mhl.css';
import '../../css/c/cbf0mmthl.css';
import '../../css/u/uju5t3m2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-sz2z30j secondary"/><g class="dt0cm9dhy primary"><path class="a43ax-bga"/><path class="rmoaf9mhl"/><path class="cbf0mmthl"/><path class="uju5t3m2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dumbbell-duo" {...props}></Icon>
