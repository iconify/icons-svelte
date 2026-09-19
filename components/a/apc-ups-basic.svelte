<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny_a88zfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny_a88zfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:apc-ups-basic" {...props}></Icon>
