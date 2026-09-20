<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amf6pcb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amf6pcb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-drive-logo-2" {...props}></Icon>
