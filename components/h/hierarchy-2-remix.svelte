<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk4ja887m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vk4ja887m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hierarchy-2-remix" {...props}></Icon>
