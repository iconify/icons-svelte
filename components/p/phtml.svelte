<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc4hxmbhx.css';
import '../../css/s/swcymbbdq.css';
import '../../css/e/e33e2gb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":18};
const content = `<g class="zc4hxmbhx"><path class="swcymbbdq"/><path class="e33e2gb6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:phtml" {...props}></Icon>
