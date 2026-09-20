<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdp06ek3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":74,"height":74};
const content = `<path class="sdp06ek3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:biome" {...props}></Icon>
