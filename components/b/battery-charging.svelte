<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xqpnc4m6o.css';
import '../../css/g/go5n_1h8p.css';
import '../../css/g/gt3_0hbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xqpnc4m6o"/><path class="go5n_1h8p wm-a"/><path class="gt3_0hbgl wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:battery-charging" {...props}></Icon>
