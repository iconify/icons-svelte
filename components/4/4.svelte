<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbij93xzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="fbij93xzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:4" {...props}></Icon>
