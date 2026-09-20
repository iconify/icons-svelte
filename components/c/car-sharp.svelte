<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0dyo-b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0dyo-b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:car-sharp" {...props}></Icon>
