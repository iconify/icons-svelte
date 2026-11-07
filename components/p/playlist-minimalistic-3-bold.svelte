<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siidedcrr.css';
import '../../css/v/vcg1j4bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="siidedcrr"/><path class="vcg1j4bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-minimalistic-3-bold" {...props}></Icon>
