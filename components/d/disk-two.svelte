<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n3e719fvy.css';
import '../../css/k/kegtm87dt.css';
import '../../css/n/ncqff0p4t.css';
import '../../css/d/dxh8x6bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="n3e719fvy"/><path class="kegtm87dt"/><circle class="ncqff0p4t"/><circle class="dxh8x6bps"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:disk-two" {...props}></Icon>
