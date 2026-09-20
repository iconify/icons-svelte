<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zos92rv0b.css';
import '../../css/a/aqg12fsbq.css';
import '../../css/z/z7yk1fbeb.css';
import '../../css/j/juc_n8brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="zos92rv0b"/><path class="aqg12fsbq"/><path class="z7yk1fbeb"/><path class="juc_n8brf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-kameleon-color:crosshair-duo" {...props}></Icon>
