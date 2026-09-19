<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq28njb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pq28njb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ox" {...props}></Icon>
