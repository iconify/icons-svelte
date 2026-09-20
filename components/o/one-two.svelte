<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkmm94b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fkmm94b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:one-two" {...props}></Icon>
