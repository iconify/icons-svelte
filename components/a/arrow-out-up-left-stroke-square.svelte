<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j082ynusa.css';
import '../../css/l/lqhgtqdtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j082ynusa"/><path class="lqhgtqdtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-left-stroke-square" {...props}></Icon>
