<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl8ymfb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="sl8ymfb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-music-filled" {...props}></Icon>
