<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paj2y1_tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paj2y1_tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magnet" {...props}></Icon>
