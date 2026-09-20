<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sol4-bc4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sol4-bc4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:business-handshake-solid" {...props}></Icon>
