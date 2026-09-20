<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gw5io-bbr.css';
import '../../css/b/bejwiwtrh.css';
import '../../css/j/jtsi5u_mv.css';
import '../../css/p/pmoqt0k4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gw5io-bbr"/><path class="bejwiwtrh"/><path class="jtsi5u_mv"/><path clip-rule="evenodd" class="pmoqt0k4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bot-outline" {...props}></Icon>
