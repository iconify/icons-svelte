<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3gbhsg8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b3gbhsg8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ice-cream-2-remix" {...props}></Icon>
