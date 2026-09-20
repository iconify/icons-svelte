<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0w57-1ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0w57-1ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-eleven-outline" {...props}></Icon>
