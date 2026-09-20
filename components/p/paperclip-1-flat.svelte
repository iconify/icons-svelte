<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r88f92b7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r88f92b7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:paperclip-1-flat" {...props}></Icon>
