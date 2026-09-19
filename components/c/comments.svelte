<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/g/gr941wbsm.css';
import '../../css/h/h9rsgyxuw.css';
import '../../css/p/p6dgoyb0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path class="gr941wbsm"/><path class="h9rsgyxuw"/><path class="p6dgoyb0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:comments" {...props}></Icon>
