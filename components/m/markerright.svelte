<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urgc0zbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="urgc0zbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:markerright" {...props}></Icon>
