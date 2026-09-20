<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv5o5wirv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv5o5wirv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-2-ai-line" {...props}></Icon>
