<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn1kokx4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn1kokx4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:cleaning-room" {...props}></Icon>
