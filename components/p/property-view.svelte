<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/z/znqi52bou.css';
import '../../css/j/ju6djclts.css';
import '../../css/r/rsp6aac3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="znqi52bou"/><path class="ju6djclts"/><path class="rsp6aac3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:property-view" {...props}></Icon>
