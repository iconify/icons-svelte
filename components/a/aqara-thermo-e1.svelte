<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7j2apbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7j2apbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-thermo-e1" {...props}></Icon>
