<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pacc4ybvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pacc4ybvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-move-left-2-remix" {...props}></Icon>
