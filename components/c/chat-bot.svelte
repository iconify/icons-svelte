<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t275zhbkr.css';
import '../../css/v/voz2zdbvr.css';
import '../../css/s/s4f6ywbzq.css';
import '../../css/c/cgvizrltr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="t275zhbkr"/><path class="voz2zdbvr"/><path class="s4f6ywbzq"/><path class="cgvizrltr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chat-bot" {...props}></Icon>
