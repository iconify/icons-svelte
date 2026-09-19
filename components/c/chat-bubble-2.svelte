<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx94i8bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="bx94i8bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chat-bubble-2" {...props}></Icon>
