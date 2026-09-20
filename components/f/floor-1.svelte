<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itpmzgi3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itpmzgi3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:floor-1" {...props}></Icon>
