<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pizot5u_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pizot5u_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:keyboard-remix" {...props}></Icon>
