<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd4103bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd4103bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:playlist-fill" {...props}></Icon>
