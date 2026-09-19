<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/am_u226-o.css';
import '../../css/x/xn8jdabvx.css';
import '../../css/l/lpx543bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="am_u226-o"/><path class="xn8jdabvx"/><path class="lpx543bxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-smartwatch" {...props}></Icon>
