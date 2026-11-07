<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8h-3cbpv.css';
import '../../css/j/jr-ln5z8r.css';
import '../../css/t/t5k-_f5ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8h-3cbpv"/><path class="jr-ln5z8r"/><path clip-rule="evenodd" class="t5k-_f5ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:maximize-square-minimalistic-outline" {...props}></Icon>
