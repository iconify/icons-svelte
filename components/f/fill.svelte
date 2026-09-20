<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoxo5y0ru.css';
import '../../css/n/nxz2d6bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoxo5y0ru"/><path class="nxz2d6bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fill" {...props}></Icon>
