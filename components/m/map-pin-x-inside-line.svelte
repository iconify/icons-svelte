<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niczrxotn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niczrxotn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-x-inside-line" {...props}></Icon>
