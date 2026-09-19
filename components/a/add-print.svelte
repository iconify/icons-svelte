<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/g/g3bzu6tbx.css';
import '../../css/w/wwarg-bxz.css';
import '../../css/f/fm1umgbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="g3bzu6tbx"/><path class="wwarg-bxz"/><path class="fm1umgbyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:add-print" {...props}></Icon>
