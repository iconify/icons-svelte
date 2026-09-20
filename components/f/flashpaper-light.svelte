<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncm1w2prn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ncm1w2prn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flashpaper-light" {...props}></Icon>
