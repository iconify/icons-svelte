<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cw83oib4z.css';
import '../../css/t/t7upphb2s.css';
import '../../css/i/iku2ktmva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="cw83oib4z"/><path class="t7upphb2s"/><path class="iku2ktmva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:person-golfing" {...props}></Icon>
