<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvqe86bhm.css';
import '../../css/p/ps3_ptnuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jvqe86bhm"/><path class="ps3_ptnuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dollar-minimalistic-bold-duotone" {...props}></Icon>
