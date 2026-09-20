<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/elns7ebwh.css';
import '../../css/w/w-_t-lb4p.css';
import '../../css/l/l_1wr2zvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="elns7ebwh"/><rect class="w-_t-lb4p"/><rect class="l_1wr2zvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:bar-graph" {...props}></Icon>
