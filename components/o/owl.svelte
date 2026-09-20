<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhc2ufb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhc2ufb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:owl" {...props}></Icon>
