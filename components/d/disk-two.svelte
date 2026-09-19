<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n3e719fvy.css';
import '../../css/q/qg6_0jboy.css';
import '../../css/b/bxexw5b-v.css';
import '../../css/n/ncqff0p4t.css';
import '../../css/d/dxh8x6bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="n3e719fvy"/><path class="qg6_0jboy"/><path class="bxexw5b-v"/><circle class="ncqff0p4t"/><circle class="dxh8x6bps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:disk-two" {...props}></Icon>
