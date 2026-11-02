<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs4gddbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cs4gddbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-upscale-line" {...props}></Icon>
