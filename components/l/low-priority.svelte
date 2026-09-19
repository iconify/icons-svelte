<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si1zmcbxh.css';
import '../../css/f/fvtlxtbin.css';
import '../../css/o/o16hhbcdh.css';
import '../../css/a/akuniccwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="si1zmcbxh"/><g class="fvtlxtbin"><path class="o16hhbcdh"/><path class="akuniccwg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:low-priority" {...props}></Icon>
