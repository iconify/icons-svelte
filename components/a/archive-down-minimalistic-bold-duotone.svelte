<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke6bcb_hh.css';
import '../../css/k/k_ae5dbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ke6bcb_hh"/><path clip-rule="evenodd" class="k_ae5dbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-minimalistic-bold-duotone" {...props}></Icon>
