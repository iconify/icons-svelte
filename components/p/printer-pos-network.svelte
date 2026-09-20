<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxh0shtie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxh0shtie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-pos-network" {...props}></Icon>
