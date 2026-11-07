<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwa9eupgf.css';
import '../../css/q/qmc5ik8au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwa9eupgf"/><path clip-rule="evenodd" class="qmc5ik8au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-check-bold-duotone" {...props}></Icon>
