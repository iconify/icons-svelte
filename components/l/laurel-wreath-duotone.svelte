<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rflspu-1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rflspu-1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:laurel-wreath-duotone" {...props}></Icon>
