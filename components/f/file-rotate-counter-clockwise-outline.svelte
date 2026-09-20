<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpwsafsix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpwsafsix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-rotate-counter-clockwise-outline" {...props}></Icon>
