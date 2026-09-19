<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm3ivccum.css';
import '../../css/q/qvwh-3bss.css';
import '../../css/r/rw-j_20-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="vm3ivccum"><path clip-rule="evenodd" class="qvwh-3bss"/><path class="rw-j_20-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:inner-shadow-right" {...props}></Icon>
