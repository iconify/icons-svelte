<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ukw3xqbut.css';
import '../../css/q/qj10p8mvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ukw3xqbut"/><path class="qj10p8mvv wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bath" {...props}></Icon>
