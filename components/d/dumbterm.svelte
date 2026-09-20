<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl0fpxpgn.css';
import '../../css/w/wci5zzb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="wl0fpxpgn"/><path class="wci5zzb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbterm" {...props}></Icon>
