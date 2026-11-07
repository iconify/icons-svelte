<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsd2d9bea.css';
import '../../css/y/yvm5pb94k.css';
import '../../css/b/bd2_93bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsd2d9bea"/><path class="yvm5pb94k"/><path class="bd2_93bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-minimalistic-bold" {...props}></Icon>
