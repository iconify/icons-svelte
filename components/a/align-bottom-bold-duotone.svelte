<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s4lmu1bbq.css';
import '../../css/w/weko16myo.css';
import '../../css/f/fwgp1tb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s4lmu1bbq"/><path class="weko16myo"/><path clip-rule="evenodd" class="fwgp1tb4z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-bottom-bold-duotone" {...props}></Icon>
