<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ix8txo7ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ix8txo7ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netbird-dark" {...props}></Icon>
