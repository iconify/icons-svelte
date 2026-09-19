<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/bub5ysbln.css';
import '../../css/w/w2tzu254s.css';
import '../../css/p/pzccn-q-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="bub5ysbln"/><path class="w2tzu254s"/><path class="pzccn-q-b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:other" {...props}></Icon>
