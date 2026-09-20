<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs21tvndn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs21tvndn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mic-sharp" {...props}></Icon>
