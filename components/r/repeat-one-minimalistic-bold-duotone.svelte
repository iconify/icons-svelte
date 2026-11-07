<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziumw9htl.css';
import '../../css/l/ltth4zvne.css';
import '../../css/l/lrv4oobuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ziumw9htl"/><path clip-rule="evenodd" class="ltth4zvne"/><path class="lrv4oobuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-one-minimalistic-bold-duotone" {...props}></Icon>
