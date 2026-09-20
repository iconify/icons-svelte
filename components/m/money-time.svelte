<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/n/nvk7ukbau.css';
import '../../css/d/d7_g8gbsv.css';
import '../../css/z/zyhn94bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="nvk7ukbau"/><path class="d7_g8gbsv"/><path class="zyhn94bau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-time" {...props}></Icon>
