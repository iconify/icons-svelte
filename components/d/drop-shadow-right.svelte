<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/d/drvoadt8u.css';
import '../../css/z/zzmzu9bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path clip-rule="evenodd" class="drvoadt8u"/><path class="zzmzu9bzw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:drop-shadow-right" {...props}></Icon>
