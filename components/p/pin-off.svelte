<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l992fn8dq.css';
import '../../css/v/vcqc0q5py.css';
import '../../css/s/s5vsshbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l992fn8dq"/><path class="vcqc0q5py"/><path class="s5vsshbss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pin-off" {...props}></Icon>
