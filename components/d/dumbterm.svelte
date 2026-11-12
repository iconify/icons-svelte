<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pby_48b_c.css';
import '../../css/w/wci5zzb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="pby_48b_c"/><path class="wci5zzb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbterm" {...props}></Icon>
