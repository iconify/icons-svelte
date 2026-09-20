<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g0z04lmhk.css';
import '../../css/n/np24xwb0n.css';
import '../../css/u/upk2z-g3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g0z04lmhk"/><path class="np24xwb0n"/><path class="upk2z-g3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:repeat" {...props}></Icon>
