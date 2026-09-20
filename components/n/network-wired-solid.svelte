<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tiwx7ab7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tiwx7ab7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:network-wired-solid" {...props}></Icon>
