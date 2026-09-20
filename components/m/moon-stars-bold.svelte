<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qazllkbmt.css';
import '../../css/h/hdgw87rbq.css';
import '../../css/t/t5yx02b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qazllkbmt"/><path class="hdgw87rbq"/><path class="t5yx02b1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-stars-bold" {...props}></Icon>
