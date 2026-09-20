<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4r97vg-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4r97vg-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:infinity-sharp" {...props}></Icon>
