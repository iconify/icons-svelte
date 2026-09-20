<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwa8e7bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwa8e7bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:calendar-export" {...props}></Icon>
