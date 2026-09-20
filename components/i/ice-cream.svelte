<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxtd5ob1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jxtd5ob1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:ice-cream" {...props}></Icon>
