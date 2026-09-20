<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv405_04e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv405_04e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rupee-2-line" {...props}></Icon>
