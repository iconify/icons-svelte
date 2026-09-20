<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk51cfb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xk51cfb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-bend-right-down-2-flat" {...props}></Icon>
