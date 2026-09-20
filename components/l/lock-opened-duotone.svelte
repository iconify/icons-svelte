<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frndcpb0j.css';
import '../../css/t/tn4b2zsid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frndcpb0j"/><path class="tn4b2zsid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:lock-opened-duotone" {...props}></Icon>
