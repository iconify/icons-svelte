<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz7dlcc-l.css';
import '../../css/d/dhqx3vboc.css';
import '../../css/b/b87hwbboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="tz7dlcc-l"><path class="dhqx3vboc"/><path class="b87hwbboa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:javascript" {...props}></Icon>
