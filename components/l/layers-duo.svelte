<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imhjn0jvd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/x5p80bb3e.css';
import '../../css/v/vqef7sbpb.css';
import '../../css/k/ky1-w1byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imhjn0jvd secondary"/><g class="dt0cm9dhy primary"><path class="x5p80bb3e"/><path class="vqef7sbpb"/><path class="ky1-w1byj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-duo" {...props}></Icon>
