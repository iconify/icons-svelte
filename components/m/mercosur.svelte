<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmibc4bxr.css';
import '../../css/p/pvppo8lbv.css';
import '../../css/r/rp7v3sbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="nmibc4bxr"/><path class="pvppo8lbv"/><path class="rp7v3sbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:mercosur" {...props}></Icon>
