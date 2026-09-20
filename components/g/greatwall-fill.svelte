<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moryof8mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moryof8mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:greatwall-fill" {...props}></Icon>
