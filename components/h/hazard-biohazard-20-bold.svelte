<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcia1ds6l.css';
import '../../css/u/u8ausac2g.css';
import '../../css/x/xufwpsbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pcia1ds6l"/><path class="u8ausac2g"/><path class="xufwpsbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-biohazard-20-bold" {...props}></Icon>
