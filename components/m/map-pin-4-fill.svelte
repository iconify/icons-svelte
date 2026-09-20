<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trbhibc5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trbhibc5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-4-fill" {...props}></Icon>
