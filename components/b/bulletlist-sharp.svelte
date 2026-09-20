<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3-nn-bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3-nn-bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:bulletlist-sharp" {...props}></Icon>
