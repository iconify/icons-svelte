<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gb-723yon.css';
import '../../css/q/q4oz3o56q.css';
import '../../css/b/b0egytfya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gb-723yon"/><path class="q4oz3o56q"/><path clip-rule="evenodd" class="b0egytfya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-quote-bold" {...props}></Icon>
