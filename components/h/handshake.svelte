<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piyd2nbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="piyd2nbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:handshake" {...props}></Icon>
