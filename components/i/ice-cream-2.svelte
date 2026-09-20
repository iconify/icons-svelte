<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlsupxbzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="dlsupxbzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ice-cream-2" {...props}></Icon>
