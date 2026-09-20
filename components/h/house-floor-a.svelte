<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yco4--zyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yco4--zyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-floor-a" {...props}></Icon>
