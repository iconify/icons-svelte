<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl8r6mbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vl8r6mbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:globe" {...props}></Icon>
