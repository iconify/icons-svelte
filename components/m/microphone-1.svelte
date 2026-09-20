<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbcv2ibqv.css';
import '../../css/q/q9u93xp0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lbcv2ibqv"/><path class="q9u93xp0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:microphone-1" {...props}></Icon>
