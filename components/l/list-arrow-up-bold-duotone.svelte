<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtjo_wb4r.css';
import '../../css/q/qj8dnmmks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dtjo_wb4r"/><path class="qj8dnmmks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-up-bold-duotone" {...props}></Icon>
