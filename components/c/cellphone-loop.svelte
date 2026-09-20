<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/raphvibhn.css';
import '../../css/c/cjxzckb3x.css';
import '../../css/i/i4ctr12sy.css';
import '../../css/m/m8tiflbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="raphvibhn"/><path clip-rule="evenodd" class="cjxzckb3x"/><path clip-rule="evenodd" class="i4ctr12sy"/><path clip-rule="evenodd" class="m8tiflbie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:cellphone-loop" {...props}></Icon>
