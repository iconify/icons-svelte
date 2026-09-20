<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6zlonm3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x6zlonm3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:power" {...props}></Icon>
