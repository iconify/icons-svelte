<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1qkuv0mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u1qkuv0mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:proxmox-logo-solid" {...props}></Icon>
