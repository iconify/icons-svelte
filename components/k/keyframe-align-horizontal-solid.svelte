<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-l1pd0_w.css';
import '../../css/y/y5u96sb9x.css';
import '../../css/z/zjhnhpypo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path class="y5u96sb9x"/><path clip-rule="evenodd" class="zjhnhpypo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:keyframe-align-horizontal-solid" {...props}></Icon>
