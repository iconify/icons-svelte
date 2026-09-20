<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l07xxkbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path class="l07xxkbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gotify-light" {...props}></Icon>
