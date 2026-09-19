<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gemdoabek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gemdoabek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chat-bubble-text-fill" {...props}></Icon>
