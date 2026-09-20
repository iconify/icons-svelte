<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivr_cpdrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivr_cpdrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:membercard-sharp" {...props}></Icon>
