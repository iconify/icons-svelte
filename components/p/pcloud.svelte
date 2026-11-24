<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5n0tdbry.css';
import '../../css/v/vfy3xytew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z5n0tdbry"/><path class="vfy3xytew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pcloud" {...props}></Icon>
