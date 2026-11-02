<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmcjodbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmcjodbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-ai-line" {...props}></Icon>
