<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8nlrybbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8nlrybbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:brackets-content-sharp" {...props}></Icon>
