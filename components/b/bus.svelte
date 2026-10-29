<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/z3cb_j7ez.css';
import '../../css/q/q0z4nob4z.css';
import '../../css/i/ild3phboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="z3cb_j7ez"/><path class="q0z4nob4z wm-a"/><path class="ild3phboo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bus" {...props}></Icon>
