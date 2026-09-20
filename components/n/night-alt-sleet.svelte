<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdam__0oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="fdam__0oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-alt-sleet" {...props}></Icon>
