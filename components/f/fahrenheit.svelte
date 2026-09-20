<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foac8gxdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="foac8gxdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:fahrenheit" {...props}></Icon>
