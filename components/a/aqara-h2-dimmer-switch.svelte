<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um8f6_zry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um8f6_zry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-h2-dimmer-switch" {...props}></Icon>
