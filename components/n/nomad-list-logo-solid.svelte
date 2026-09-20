<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw9g_xb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mw9g_xb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:nomad-list-logo-solid" {...props}></Icon>
