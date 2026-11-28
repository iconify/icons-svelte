<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tun7kpbmr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/v8w075vzh.css';
import '../../css/i/i8vw3obrx.css';
import '../../css/f/febcbpb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tun7kpbmr"/><g class="dt0cm9dhy primary"><path class="v8w075vzh"/><path class="i8vw3obrx"/><path class="febcbpb6e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-input-duo" {...props}></Icon>
