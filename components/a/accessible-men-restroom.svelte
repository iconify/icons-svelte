<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwv5vgb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwv5vgb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:accessible-men-restroom" {...props}></Icon>
