<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf_0tfbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sf_0tfbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-dark" {...props}></Icon>
