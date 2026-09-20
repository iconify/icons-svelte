<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrz70jbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrz70jbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:monument-line" {...props}></Icon>
