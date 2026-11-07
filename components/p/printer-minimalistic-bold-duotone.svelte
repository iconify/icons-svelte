<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsd2d9bea.css';
import '../../css/b/bd2_93bmd.css';
import '../../css/k/k7eozybwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsd2d9bea"/><path class="bd2_93bmd"/><path class="k7eozybwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-minimalistic-bold-duotone" {...props}></Icon>
