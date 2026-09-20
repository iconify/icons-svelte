<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiw4zpdte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="hiw4zpdte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-23" {...props}></Icon>
