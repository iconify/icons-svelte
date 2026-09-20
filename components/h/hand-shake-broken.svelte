<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/t6-jjabzv.css';
import '../../css/r/rwyyhnb2f.css';
import '../../css/e/e8gjtcbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="t6-jjabzv"/><path class="rwyyhnb2f"/><path class="e8gjtcbgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-shake-broken" {...props}></Icon>
