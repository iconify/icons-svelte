<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0wlds3qh.css';
import '../../css/u/uz8c7kbrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0wlds3qh"/><path clip-rule="evenodd" class="uz8c7kbrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bug-play-filled" {...props}></Icon>
