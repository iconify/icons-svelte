<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/e1dt95bvo.css';
import '../../css/n/nk-f8ubml.css';
import '../../css/o/omnrth6_m.css';
import '../../css/u/u-himcq2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e1dt95bvo"/><path class="nk-f8ubml"/><path class="omnrth6_m"/><path class="u-himcq2i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-playlist" {...props}></Icon>
