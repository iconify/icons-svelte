<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhtfkdvai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mhtfkdvai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:chat-plus-bold" {...props}></Icon>
