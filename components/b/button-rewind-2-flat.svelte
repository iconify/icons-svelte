<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2a3fl7wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p2a3fl7wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:button-rewind-2-flat" {...props}></Icon>
