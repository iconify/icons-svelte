<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1xy5cu_z.css';
import '../../css/e/e3k62ibrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1xy5cu_z"/><path class="e3k62ibrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-handshake-filled" {...props}></Icon>
