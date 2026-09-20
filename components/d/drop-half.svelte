<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4g6uk3ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4g6uk3ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:drop-half" {...props}></Icon>
