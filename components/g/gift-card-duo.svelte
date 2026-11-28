<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezv1mcchc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ammxg4bjk.css';
import '../../css/a/ah6sqybwi.css';
import '../../css/z/zec44e7ke.css';
import '../../css/w/wppt0-b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezv1mcchc secondary"/><g class="dt0cm9dhy primary"><path class="ammxg4bjk"/><path class="ah6sqybwi"/><path class="zec44e7ke"/><path class="wppt0-b2x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:gift-card-duo" {...props}></Icon>
