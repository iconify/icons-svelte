<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw3_0y36g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gw3_0y36g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-letter-boxed-light" {...props}></Icon>
