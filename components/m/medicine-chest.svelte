<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xh974hv9a.css';
import '../../css/x/xdhwcn32g.css';
import '../../css/f/ffmgiytrk.css';
import '../../css/k/ker0gib4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="xh974hv9a"/><path class="xdhwcn32g"/><path class="ffmgiytrk"/><path class="ker0gib4l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:medicine-chest" {...props}></Icon>
