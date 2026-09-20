<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm9w7kb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tm9w7kb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:airsonic-light" {...props}></Icon>
