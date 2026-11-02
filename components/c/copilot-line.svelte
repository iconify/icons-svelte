<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atv00kbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atv00kbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copilot-line" {...props}></Icon>
