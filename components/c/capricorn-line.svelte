<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0mdmyy9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0mdmyy9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:capricorn-line" {...props}></Icon>
