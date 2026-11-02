<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze9iq3bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze9iq3bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-upscale-fill" {...props}></Icon>
