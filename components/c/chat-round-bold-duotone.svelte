<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3zoptn7o.css';
import '../../css/g/gc83r37zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3zoptn7o"/><path class="gc83r37zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-bold-duotone" {...props}></Icon>
