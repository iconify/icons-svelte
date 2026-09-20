<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm0xpbe5i.css';
import '../../css/s/sla_3qh9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hm0xpbe5i"/><path class="sla_3qh9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fandom" {...props}></Icon>
