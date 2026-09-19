<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnkn5nb4l.css';
import '../../css/y/yytmiewvb.css';
import '../../css/x/xt121f3ic.css';
import '../../css/v/vhm2djnqg.css';
import '../../css/d/d3co6xbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cnkn5nb4l"><path class="yytmiewvb"/><path class="xt121f3ic"/><path class="vhm2djnqg"/><path class="d3co6xbya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:javascript-react" {...props}></Icon>
