<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/i/imnimkbei.css';
import '../../css/e/ed-8o3t8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="h01tyzbfu"><path class="imnimkbei"/><path class="ed-8o3t8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:play-outline" {...props}></Icon>
