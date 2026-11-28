<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8rzabwzd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f32u92wnr.css';
import '../../css/r/rpixg5b7g.css';
import '../../css/r/rp-107qrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8rzabwzd secondary"/><g class="dt0cm9dhy primary"><path class="f32u92wnr"/><path class="rpixg5b7g"/><path class="rp-107qrc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-sparkles-duo" {...props}></Icon>
