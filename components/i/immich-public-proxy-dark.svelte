<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e10jzhbge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e10jzhbge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:immich-public-proxy-dark" {...props}></Icon>
