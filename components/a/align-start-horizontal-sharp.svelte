<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx_32i24f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx_32i24f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:align-start-horizontal-sharp" {...props}></Icon>
