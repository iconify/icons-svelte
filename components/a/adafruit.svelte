<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6a_cgazp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6a_cgazp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adafruit" {...props}></Icon>
