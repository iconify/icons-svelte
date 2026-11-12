<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhrhopb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dhrhopb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:obs-bygg-dark" {...props}></Icon>
