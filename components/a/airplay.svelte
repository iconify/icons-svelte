<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwxqfcx0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="vwxqfcx0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:airplay" {...props}></Icon>
