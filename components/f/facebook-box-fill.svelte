<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzv4l5-8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzv4l5-8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:facebook-box-fill" {...props}></Icon>
