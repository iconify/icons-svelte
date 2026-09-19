<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-_2_25ob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-_2_25ob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:cake-candles-solid" {...props}></Icon>
