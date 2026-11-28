<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mdipw5bzh.css';
import '../../css/m/m1ue8zbct.css';
import '../../css/d/d962hab1x.css';
import '../../css/j/jqu4q6bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mdipw5bzh"/><path class="m1ue8zbct"/><path class="d962hab1x"/><path class="jqu4q6bku"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-key" {...props}></Icon>
