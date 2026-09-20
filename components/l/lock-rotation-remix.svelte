<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pge5z1bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pge5z1bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:lock-rotation-remix" {...props}></Icon>
