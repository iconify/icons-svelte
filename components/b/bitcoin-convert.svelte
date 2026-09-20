<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/f-ut3mb7m.css';
import '../../css/t/t69um4bmx.css';
import '../../css/y/y6qv0pb5h.css';
import '../../css/w/wie0hy52g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-ut3mb7m"/><path class="t69um4bmx"/><path class="y6qv0pb5h"/><path class="wie0hy52g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bitcoin-convert" {...props}></Icon>
