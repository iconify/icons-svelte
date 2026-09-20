<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulo34lq1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulo34lq1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:eraser" {...props}></Icon>
