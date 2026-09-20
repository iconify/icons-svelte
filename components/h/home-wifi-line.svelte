<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1vj40xrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1vj40xrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:home-wifi-line" {...props}></Icon>
