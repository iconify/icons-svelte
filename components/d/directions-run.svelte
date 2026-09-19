<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6_y8j3lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":464};
const content = `<path class="n6_y8j3lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:directions-run" {...props}></Icon>
