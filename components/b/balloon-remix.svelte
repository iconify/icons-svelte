<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnul87b3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vnul87b3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:balloon-remix" {...props}></Icon>
