<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7qn5succ.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7qn5succ"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-ai-fill" {...props}></Icon>
