<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dooa6g5cx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dooa6g5cx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-multiple-window-remix" {...props}></Icon>
