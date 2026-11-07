<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziumw9htl.css';
import '../../css/l/ltth4zvne.css';
import '../../css/t/t4p0zib2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ziumw9htl"/><path clip-rule="evenodd" class="ltth4zvne"/><path class="t4p0zib2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:repeat-one-minimalistic-bold" {...props}></Icon>
