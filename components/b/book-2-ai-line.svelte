<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcaesc56o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcaesc56o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-2-ai-line" {...props}></Icon>
