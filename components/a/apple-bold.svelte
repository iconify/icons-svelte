<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m45ig3bmy.css';
import '../../css/x/xjhwnvbgl.css';
import '../../css/y/yh5ahcbjw.css';
import '../../css/j/japg61bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m45ig3bmy"/><path class="xjhwnvbgl"/><path clip-rule="evenodd" class="yh5ahcbjw"/><path class="japg61bou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:apple-bold" {...props}></Icon>
