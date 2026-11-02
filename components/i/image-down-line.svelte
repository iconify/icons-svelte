<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5e_d4lum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5e_d4lum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:image-down-line" {...props}></Icon>
