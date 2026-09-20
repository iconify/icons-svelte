<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1rbdisyq.css';
import '../../css/f/frpnumb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1rbdisyq"/><path class="frpnumb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:readmeabook-dark" {...props}></Icon>
