<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv-vo6qjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tv-vo6qjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:location-outline" {...props}></Icon>
