<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_oj2pm_r.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/us6kxt9tp.css';
import '../../css/g/gws5glbsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_oj2pm_r secondary"/><g class="dt0cm9dhy primary"><path class="us6kxt9tp"/><path class="gws5glbsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-check-duo" {...props}></Icon>
