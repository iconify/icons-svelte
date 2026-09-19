<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imc306b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imc306b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:microphone-outline" {...props}></Icon>
