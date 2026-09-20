<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pte5rzrpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pte5rzrpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mastodon-dark" {...props}></Icon>
