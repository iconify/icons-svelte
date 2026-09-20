<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8kdyub3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8kdyub3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:openvpn-logo-solid" {...props}></Icon>
