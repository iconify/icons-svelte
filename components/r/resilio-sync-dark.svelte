<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6_c0xb0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h6_c0xb0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:resilio-sync-dark" {...props}></Icon>
