<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-e1x6brn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-e1x6brn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:google-play" {...props}></Icon>
