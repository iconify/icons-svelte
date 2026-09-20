<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gli4g3-ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gli4g3-ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-l" {...props}></Icon>
