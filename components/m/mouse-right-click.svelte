<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih6_8hbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih6_8hbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mouse-right-click" {...props}></Icon>
