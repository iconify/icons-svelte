<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnn6srcuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnn6srcuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-exclamation" {...props}></Icon>
