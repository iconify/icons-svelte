<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/j49_jenke.css';
import '../../css/f/f3tg6ebbt.css';
import '../../css/h/hm38-ccpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="j49_jenke"/><path class="f3tg6ebbt wm-a"/><path class="hm38-ccpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ethernet-port-duo" {...props}></Icon>
