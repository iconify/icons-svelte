<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v96dn9r4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v96dn9r4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-clef-bass" {...props}></Icon>
