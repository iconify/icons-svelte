<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzoimlb-v.css';
import '../../css/p/pemqbc__o.css';
import '../../css/p/p3q4orbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wzoimlb-v"/><path class="pemqbc__o"/><path class="p3q4orbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:passkey-20" {...props}></Icon>
