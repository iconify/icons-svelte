<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdpnogbdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdpnogbdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:phone-question" {...props}></Icon>
