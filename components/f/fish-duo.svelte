<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcni6qbqh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lvd82jv5z.css';
import '../../css/t/t92y3z_3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcni6qbqh secondary"/><g class="dt0cm9dhy primary"><path class="lvd82jv5z"/><path class="t92y3z_3b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fish-duo" {...props}></Icon>
