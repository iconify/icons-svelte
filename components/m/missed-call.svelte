<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1vrx_b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1vrx_b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:missed-call" {...props}></Icon>
