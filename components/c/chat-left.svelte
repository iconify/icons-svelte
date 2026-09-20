<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mszonib9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mszonib9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:chat-left" {...props}></Icon>
