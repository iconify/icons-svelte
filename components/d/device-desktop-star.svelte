<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa5wd-b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fa5wd-b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-star" {...props}></Icon>
