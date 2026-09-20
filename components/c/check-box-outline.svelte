<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-lwxf4od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-lwxf4od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:check-box-outline" {...props}></Icon>
