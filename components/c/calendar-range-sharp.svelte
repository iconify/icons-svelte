<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drowvd1zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drowvd1zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-range-sharp" {...props}></Icon>
