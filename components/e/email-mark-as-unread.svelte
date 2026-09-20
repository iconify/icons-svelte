<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pracb0xpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pracb0xpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-mark-as-unread" {...props}></Icon>
