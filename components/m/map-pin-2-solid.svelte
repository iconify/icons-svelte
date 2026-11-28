<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5r3cacbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5r3cacbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:map-pin-2-solid" {...props}></Icon>
