<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lymp3m9ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lymp3m9ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:map-filled" {...props}></Icon>
