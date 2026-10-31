<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_dxl-1rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_dxl-1rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:code-block-fill-round" {...props}></Icon>
