<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8b_cacmv.css';
import '../../css/h/hdwbqmb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k8b_cacmv"/><path class="hdwbqmb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-minimalistic-3-bold-duotone" {...props}></Icon>
