<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvj6_sntz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvj6_sntz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cake-sharp" {...props}></Icon>
