<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc6ytf2nz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hc6ytf2nz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:audio-description2" {...props}></Icon>
