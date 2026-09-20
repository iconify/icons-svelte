<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6yz8kxoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g6yz8kxoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quetre-dark" {...props}></Icon>
