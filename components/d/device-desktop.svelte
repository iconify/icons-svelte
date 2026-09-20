<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1a95zbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1a95zbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop" {...props}></Icon>
