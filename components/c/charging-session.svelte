<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/mf1qfwb3p.css';
import '../../css/c/c3ra92qkt.css';
import '../../css/q/qvpu09b-s.css';
import '../../css/r/ru3w0x1yt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mf1qfwb3p"/><path class="c3ra92qkt"/><path class="qvpu09b-s"/><path class="ru3w0x1yt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:charging-session" {...props}></Icon>
