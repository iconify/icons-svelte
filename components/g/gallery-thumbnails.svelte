<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xncha08gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xncha08gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gallery-thumbnails" {...props}></Icon>
