<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nucn65bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nucn65bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-heart" {...props}></Icon>
