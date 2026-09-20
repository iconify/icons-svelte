<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uifvd8bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uifvd8bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pin-line" {...props}></Icon>
