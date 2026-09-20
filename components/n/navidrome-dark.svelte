<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcy5gh-xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dcy5gh-xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:navidrome-dark" {...props}></Icon>
