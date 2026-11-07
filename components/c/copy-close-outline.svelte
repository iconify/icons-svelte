<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd_-mkbbv.css';
import '../../css/d/dmbrnfbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd_-mkbbv"/><path clip-rule="evenodd" class="dmbrnfbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-close-outline" {...props}></Icon>
