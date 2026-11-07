<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev04l0b7x.css';
import '../../css/l/l15q94brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev04l0b7x"/><path clip-rule="evenodd" class="l15q94brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-school-bold-duotone" {...props}></Icon>
