<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq51h4bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq51h4bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:camera-sparkle-round" {...props}></Icon>
