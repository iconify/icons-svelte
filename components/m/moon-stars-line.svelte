<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itv2ip3np.css';
import '../../css/w/wio05-bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itv2ip3np"/><path clip-rule="evenodd" class="wio05-bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moon-stars-line" {...props}></Icon>
