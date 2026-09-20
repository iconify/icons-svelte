<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glymc6bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="glymc6bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bunkerweb-dark" {...props}></Icon>
