<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk-_l-3je.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vk-_l-3je"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pen-tool-remix" {...props}></Icon>
