<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfbbzrx-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gfbbzrx-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:map-vertical-filled" {...props}></Icon>
