<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz7dlcc-l.css';
import '../../css/a/ah8b_-xeq.css';
import '../../css/r/rqh9r0b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="tz7dlcc-l"><path class="ah8b_-xeq"/><path class="rqh9r0b_f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:browserslist" {...props}></Icon>
