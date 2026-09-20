<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkxo5wbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkxo5wbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bottle-wine" {...props}></Icon>
