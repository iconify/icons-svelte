<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibkxrtjjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibkxrtjjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-ai-line" {...props}></Icon>
