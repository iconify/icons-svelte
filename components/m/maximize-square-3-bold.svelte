<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivgsmkbsz.css';
import '../../css/x/x_vwkib6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivgsmkbsz"/><path clip-rule="evenodd" class="x_vwkib6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:maximize-square-3-bold" {...props}></Icon>
