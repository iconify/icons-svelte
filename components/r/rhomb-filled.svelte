<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlg3n8bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vlg3n8bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rhomb-filled" {...props}></Icon>
