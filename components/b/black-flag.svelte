<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv6i72hwb.css';
import '../../css/d/dqh0sx9gc.css';
import '../../css/d/dcqdxh5zc.css';
import '../../css/i/i_q9gubdm.css';
import '../../css/u/ur9ub8kkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="mv6i72hwb"/><path class="dqh0sx9gc"/><g class="dcqdxh5zc"><path class="i_q9gubdm"/><path class="ur9ub8kkl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-flag" {...props}></Icon>
