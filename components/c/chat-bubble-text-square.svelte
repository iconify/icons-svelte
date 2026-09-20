<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrk17h_3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wrk17h_3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chat-bubble-text-square" {...props}></Icon>
