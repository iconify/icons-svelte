<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/yijx6hbni.css';
import '../../css/i/imsjpsbtj.css';
import '../../css/g/g1s8iiuoa.css';
import '../../css/r/r_9v_xb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="yijx6hbni"/><path class="imsjpsbtj"/><path class="g1s8iiuoa"/><path class="r_9v_xb3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:chrome" {...props}></Icon>
