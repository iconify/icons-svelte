<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww8qfyb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ww8qfyb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:map-ltr" {...props}></Icon>
