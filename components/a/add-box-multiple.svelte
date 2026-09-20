<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avtfwobpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avtfwobpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:add-box-multiple" {...props}></Icon>
