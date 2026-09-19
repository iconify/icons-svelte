<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vf52vtinf.css';
import '../../css/r/rsmyz1hsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vf52vtinf"/><path class="rsmyz1hsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-event-streams" {...props}></Icon>
