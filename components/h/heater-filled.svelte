<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxekpbbhl.css';
import '../../css/i/i-u_0kb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxekpbbhl"/><path class="i-u_0kb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heater-filled" {...props}></Icon>
