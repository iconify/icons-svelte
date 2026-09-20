<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpl6xib5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fpl6xib5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:printables-light" {...props}></Icon>
