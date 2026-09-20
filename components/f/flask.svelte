<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6a8w3bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6a8w3bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:flask" {...props}></Icon>
