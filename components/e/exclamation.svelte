<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vad9-vkwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="vad9-vkwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:exclamation" {...props}></Icon>
