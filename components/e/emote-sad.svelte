<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b57cg5bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="b57cg5bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:emote-sad" {...props}></Icon>
