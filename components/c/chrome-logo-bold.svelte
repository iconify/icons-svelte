<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv3bsr2xr.css';
import '../../css/m/mbclv28jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv3bsr2xr"/><path class="mbclv28jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:chrome-logo-bold" {...props}></Icon>
