<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nna122kyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nna122kyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-3-ai-line" {...props}></Icon>
