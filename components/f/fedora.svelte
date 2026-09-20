<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-ws7tr1v.css';
import '../../css/r/rg2p71b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-ws7tr1v"/><path class="rg2p71b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fedora" {...props}></Icon>
