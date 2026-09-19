<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv4b38b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":408};
const content = `<path class="kv4b38b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:directions-bus" {...props}></Icon>
