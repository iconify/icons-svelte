<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcw1hs52e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcw1hs52e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-4-line" {...props}></Icon>
