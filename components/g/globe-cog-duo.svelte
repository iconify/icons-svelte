<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpf1pnm8r.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o1e-g3_1s.css';
import '../../css/m/mbgo7jbwd.css';
import '../../css/d/da4on7b5f.css';
import '../../css/d/dq60wlbxs.css';
import '../../css/b/b9him6jfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpf1pnm8r secondary"/><g class="dt0cm9dhy primary"><path class="o1e-g3_1s"/><path class="mbgo7jbwd"/><path class="da4on7b5f"/><path class="dq60wlbxs"/><path class="b9him6jfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:globe-cog-duo" {...props}></Icon>
