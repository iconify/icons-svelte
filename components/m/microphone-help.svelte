<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwxxu2vds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwxxu2vds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microphone-help" {...props}></Icon>
