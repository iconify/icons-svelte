<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwhof2_ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwhof2_ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:microphone-round" {...props}></Icon>
