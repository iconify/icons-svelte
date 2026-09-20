<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/maaum7bvf.css';
import '../../css/k/kzdconb-v.css';
import '../../css/i/i9k0b6btm.css';
import '../../css/z/zsuclwbnx.css';
import '../../css/k/kspoj7vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="maaum7bvf"/><path clip-rule="evenodd" class="kzdconb-v"/><path clip-rule="evenodd" class="i9k0b6btm"/><path class="zsuclwbnx"/><path clip-rule="evenodd" class="kspoj7vnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:letter-open-circle-off" {...props}></Icon>
