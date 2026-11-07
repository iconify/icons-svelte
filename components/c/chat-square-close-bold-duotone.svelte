<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfpn6w7ca.css';
import '../../css/a/a_nbz-b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfpn6w7ca"/><path class="a_nbz-b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-close-bold-duotone" {...props}></Icon>
