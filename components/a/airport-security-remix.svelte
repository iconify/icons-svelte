<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro7masbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ro7masbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airport-security-remix" {...props}></Icon>
