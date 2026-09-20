<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1fum8bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w1fum8bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hi-events-light" {...props}></Icon>
