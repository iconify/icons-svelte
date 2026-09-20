<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhdlmtmsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhdlmtmsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:cloud-download" {...props}></Icon>
