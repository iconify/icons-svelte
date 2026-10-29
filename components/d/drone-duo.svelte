<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/s5vm4tbxd.css';
import '../../css/s/snvjfcboq.css';
import '../../css/h/hr07nwq7t.css';
import '../../css/t/t96a34een.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="s5vm4tbxd"/><path class="snvjfcboq wm-a"/><path class="hr07nwq7t"/><path class="t96a34een wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:drone-duo" {...props}></Icon>
