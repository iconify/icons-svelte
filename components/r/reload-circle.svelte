<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sse3loblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sse3loblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:reload-circle" {...props}></Icon>
