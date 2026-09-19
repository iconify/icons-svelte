<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnycbel7f.css';
import '../../css/v/vxg7h7uod.css';
import '../../css/p/poohdx77y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rnycbel7f"/><path class="vxg7h7uod"/><path class="poohdx77y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-rss" {...props}></Icon>
