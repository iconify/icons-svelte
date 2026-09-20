<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/f3u0_18rl.css';
import '../../css/w/wblmcub7l.css';
import '../../css/w/wr_ombbyr.css';
import '../../css/j/jqsf6xrbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3u0_18rl"/><path class="wblmcub7l"/><path class="wr_ombbyr"/><path class="jqsf6xrbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-dashboard" {...props}></Icon>
