<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-kxx2bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-kxx2bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:badge-5k-sharp" {...props}></Icon>
