<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e634y07gb.css';
import '../../css/w/wl3arebmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e634y07gb"/><path class="wl3arebmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:markstack-dark" {...props}></Icon>
