<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/m/mtkkfsbrb.css';
import '../../css/i/iad93baoy.css';
import '../../css/j/jcrlfrbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="mtkkfsbrb"/><path clip-rule="evenodd" class="iad93baoy"/><path class="jcrlfrbgh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bedside-two" {...props}></Icon>
