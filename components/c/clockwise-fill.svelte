<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn2x2m3bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn2x2m3bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clockwise-fill" {...props}></Icon>
