<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev04l0b7x.css';
import '../../css/y/yp-6u2b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev04l0b7x"/><path class="yp-6u2b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-add-bold-duotone" {...props}></Icon>
