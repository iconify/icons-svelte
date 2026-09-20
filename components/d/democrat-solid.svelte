<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twv9pbpkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="twv9pbpkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:democrat-solid" {...props}></Icon>
