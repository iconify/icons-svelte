<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixcdw3xng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixcdw3xng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:quote-right-duotone-round" {...props}></Icon>
