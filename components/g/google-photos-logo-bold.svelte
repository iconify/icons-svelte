<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmzf_cekc.css';
import '../../css/y/yybosibpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmzf_cekc"/><path class="yybosibpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:google-photos-logo-bold" {...props}></Icon>
