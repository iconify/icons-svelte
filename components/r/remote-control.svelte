<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0_n5sdns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":336,"height":496};
const content = `<path class="s0_n5sdns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:remote-control" {...props}></Icon>
