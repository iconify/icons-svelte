<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viv1grb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="viv1grb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-acrobat" {...props}></Icon>
