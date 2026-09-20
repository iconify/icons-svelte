<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srt0sd2qy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srt0sd2qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:battery-full-sharp" {...props}></Icon>
