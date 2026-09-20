<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/limck8wdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="limck8wdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:production-belt-solid" {...props}></Icon>
