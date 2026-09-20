<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qazllkbmt.css';
import '../../css/i/ind715bsx.css';
import '../../css/w/wh3ud5bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qazllkbmt"/><path class="ind715bsx"/><path class="wh3ud5bbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:moon-sleep-bold" {...props}></Icon>
