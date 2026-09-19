<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/b/b0xhw3gtc.css';
import '../../css/f/foyc2nb7z.css';
import '../../css/b/btfw9mbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="b0xhw3gtc"/><path class="foyc2nb7z"/><path class="btfw9mbtg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:proportional-scaling" {...props}></Icon>
