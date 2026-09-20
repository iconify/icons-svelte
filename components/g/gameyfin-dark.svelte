<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/semirj3sh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="semirj3sh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gameyfin-dark" {...props}></Icon>
