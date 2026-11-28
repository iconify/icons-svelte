<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcq6dd0my.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fa986fbos.css';
import '../../css/x/xdc556bol.css';
import '../../css/h/hfirngbmd.css';
import '../../css/x/xc1ugqj_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcq6dd0my secondary"/><g class="dt0cm9dhy primary"><path class="fa986fbos"/><path class="xdc556bol"/><path class="hfirngbmd"/><path class="xc1ugqj_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gate-or-duo" {...props}></Icon>
