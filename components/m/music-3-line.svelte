<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k93xi3wmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k93xi3wmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-3-line" {...props}></Icon>
