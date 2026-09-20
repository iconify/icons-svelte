<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7kbt2bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i7kbt2bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-music-stand-dark" {...props}></Icon>
