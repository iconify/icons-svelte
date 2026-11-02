<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruxgsbgmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruxgsbgmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-house-fill" {...props}></Icon>
