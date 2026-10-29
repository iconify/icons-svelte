<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dk_c-sb7y.css';
import '../../css/h/hzbldnbux.css';
import '../../css/v/vjpnyegoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="dk_c-sb7y"/><path class="hzbldnbux wm-a"/><path class="vjpnyegoq wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:poinsettia" {...props}></Icon>
