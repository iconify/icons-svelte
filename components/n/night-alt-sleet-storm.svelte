<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffzgqjqfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ffzgqjqfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-alt-sleet-storm" {...props}></Icon>
