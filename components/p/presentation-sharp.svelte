<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyapjotzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyapjotzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:presentation-sharp" {...props}></Icon>
