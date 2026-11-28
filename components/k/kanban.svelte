<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uacp7pu3u.css';
import '../../css/d/db-0dmlok.css';
import '../../css/x/x7vrpjlro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="uacp7pu3u"/><path class="db-0dmlok"/><path class="x7vrpjlro"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:kanban" {...props}></Icon>
