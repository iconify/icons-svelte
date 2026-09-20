<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kun_1n6hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kun_1n6hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:plex-light" {...props}></Icon>
