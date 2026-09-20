<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g19fxyhyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g19fxyhyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-cursor-2-remix" {...props}></Icon>
