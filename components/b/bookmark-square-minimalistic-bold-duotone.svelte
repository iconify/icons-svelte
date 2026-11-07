<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcid6acgw.css';
import '../../css/g/g-fa1j-ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcid6acgw"/><path class="g-fa1j-ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-square-minimalistic-bold-duotone" {...props}></Icon>
