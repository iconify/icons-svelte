<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm3w5dbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm3w5dbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oppo" {...props}></Icon>
