<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilm43_ows.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ilm43_ows"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bridge" {...props}></Icon>
