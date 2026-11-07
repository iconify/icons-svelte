<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvqe86bhm.css';
import '../../css/i/ibf2r7bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jvqe86bhm"/><path class="ibf2r7bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pin-circle-bold-duotone" {...props}></Icon>
