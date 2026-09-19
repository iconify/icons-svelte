<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqhgtqdtq.css';
import '../../css/c/c924plbqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqhgtqdtq"/><path class="c924plbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-left-square" {...props}></Icon>
