<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpqi2ybyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="fpqi2ybyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:bell-slash" {...props}></Icon>
