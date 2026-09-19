<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewbhfu7_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ewbhfu7_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-video-solid" {...props}></Icon>
