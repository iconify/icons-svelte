<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4kkt5bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w4kkt5bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:debian-dark" {...props}></Icon>
