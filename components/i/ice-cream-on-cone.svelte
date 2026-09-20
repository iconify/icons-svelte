<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isgk0lbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="isgk0lbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-cream-on-cone" {...props}></Icon>
