<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fosf2ck3z.css';
import '../../css/x/x1kqalb8d.css';
import '../../css/i/ixdq6ntaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fosf2ck3z"/><path class="x1kqalb8d"/><path clip-rule="evenodd" class="ixdq6ntaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:patient-band-alt2x-outline" {...props}></Icon>
