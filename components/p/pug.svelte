<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuw7_9_1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vuw7_9_1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:pug" {...props}></Icon>
