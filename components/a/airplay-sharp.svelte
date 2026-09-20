<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzk0swxtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzk0swxtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:airplay-sharp" {...props}></Icon>
