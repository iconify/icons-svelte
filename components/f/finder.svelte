<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/s6q5tnmex.css';
import '../../css/d/dugkeub-s.css';
import '../../css/e/ehf885ncn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s6q5tnmex"/><path class="dugkeub-s"/><path class="ehf885ncn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:finder" {...props}></Icon>
