<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qg8owzi5f.css';
import '../../css/s/sjqyd1bri.css';
import '../../css/z/z6_008b8j.css';
import '../../css/v/vskemkbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qg8owzi5f"/><rect class="sjqyd1bri"/><rect class="z6_008b8j"/><path class="vskemkbqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chart-bar-trend-up" {...props}></Icon>
