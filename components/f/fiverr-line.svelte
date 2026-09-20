<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2kd129md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2kd129md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:fiverr-line" {...props}></Icon>
