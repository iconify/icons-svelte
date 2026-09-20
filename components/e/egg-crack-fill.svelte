<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pebcm94wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pebcm94wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:egg-crack-fill" {...props}></Icon>
