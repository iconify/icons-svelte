<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p8nc0nbln.css';
import '../../css/k/kfirkk0hp.css';
import '../../css/c/cai__zb4b.css';
import '../../css/o/ofays0bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p8nc0nbln"/><path class="kfirkk0hp"/><path class="cai__zb4b"/><path class="ofays0bxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:clipboard-paste" {...props}></Icon>
