<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3c6beb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3c6beb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:mark-3" {...props}></Icon>
