<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xpx69nb4t.css';
import '../../css/k/kfqbnub9s.css';
import '../../css/s/snvrewbju.css';
import '../../css/c/c4ppv22xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xpx69nb4t"/><path class="kfqbnub9s wm-s"/><path class="snvrewbju"/><path class="c4ppv22xk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bell-plus-duo" {...props}></Icon>
