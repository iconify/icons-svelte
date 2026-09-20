<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp1h2bbup.css';
import '../../css/v/vcbva_jjq.css';
import '../../css/y/ya37qbble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xp1h2bbup"/><path class="vcbva_jjq"/><path class="ya37qbble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ente-locker-light" {...props}></Icon>
