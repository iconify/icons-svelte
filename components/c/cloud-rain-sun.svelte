<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmmx76bjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmmx76bjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:cloud-rain-sun" {...props}></Icon>
