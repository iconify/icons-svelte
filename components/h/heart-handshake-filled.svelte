<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6mxce4uq.css';
import '../../css/n/nuwhiyu0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6mxce4uq"/><path class="nuwhiyu0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-handshake-filled" {...props}></Icon>
