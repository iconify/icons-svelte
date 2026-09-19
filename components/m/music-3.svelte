<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dqapyabwu.css';
import '../../css/d/dos_yhbgg.css';
import '../../css/n/nrala8f6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dqapyabwu"/><circle class="dos_yhbgg"/><path class="nrala8f6n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:music-3" {...props}></Icon>
