<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiu3adc7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="aiu3adc7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:kiosk-14" {...props}></Icon>
