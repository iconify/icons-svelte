<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kswv2hrkj.css';
import '../../css/m/mqmycj9zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kswv2hrkj"/><path class="mqmycj9zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-off-bold-duotone" {...props}></Icon>
