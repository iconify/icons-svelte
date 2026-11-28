<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvyyz5b8g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q4o4ithkw.css';
import '../../css/k/kbxpyqdun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvyyz5b8g secondary"/><g class="dt0cm9dhy primary"><path class="q4o4ithkw"/><path class="kbxpyqdun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chess-pawn-duo" {...props}></Icon>
