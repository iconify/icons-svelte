<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeqs3cbpz.css';
import '../../css/f/fvpx17bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oeqs3cbpz"/><path class="fvpx17bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:backspace-bold-duotone" {...props}></Icon>
