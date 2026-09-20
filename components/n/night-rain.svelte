<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk9_o78-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="nk9_o78-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-rain" {...props}></Icon>
