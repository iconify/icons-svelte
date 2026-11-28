<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adm-aouqi.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wys62rbgd.css';
import '../../css/v/v0kt71byo.css';
import '../../css/o/oo4ydnuvq.css';
import '../../css/f/fo0pchbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adm-aouqi secondary"/><g class="dt0cm9dhy primary"><path class="wys62rbgd"/><path class="v0kt71byo"/><path class="oo4ydnuvq"/><path class="fo0pchbda"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:award-duo" {...props}></Icon>
