<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqv21hmdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqv21hmdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-charging-70" {...props}></Icon>
