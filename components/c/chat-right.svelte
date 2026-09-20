<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjzfa1bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gjzfa1bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:chat-right" {...props}></Icon>
