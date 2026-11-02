<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jknwwm1_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jknwwm1_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:moderate-snow-line" {...props}></Icon>
