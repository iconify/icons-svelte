<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-ul83bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-ul83bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radarr-anime-dark" {...props}></Icon>
