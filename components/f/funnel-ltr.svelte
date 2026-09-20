<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhwf4_tkf.css';
import '../../css/y/ydubk1bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vhwf4_tkf"/><path class="ydubk1bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:funnel-ltr" {...props}></Icon>
