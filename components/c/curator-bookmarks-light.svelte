<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgkp2kb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fgkp2kb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:curator-bookmarks-light" {...props}></Icon>
