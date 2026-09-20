<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl5qrebcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl5qrebcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cellphone-2-ai-fill" {...props}></Icon>
