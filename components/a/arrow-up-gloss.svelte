<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm27l8nmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm27l8nmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:arrow-up-gloss" {...props}></Icon>
