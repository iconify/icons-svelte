<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r6m16c0xn.css';
import '../../css/b/bsldfolwb.css';
import '../../css/x/xoty01rwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="r6m16c0xn"/><path class="bsldfolwb"/><path class="xoty01rwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:card-sim-duotone" {...props}></Icon>
