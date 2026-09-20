<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj4o9achs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":279.62,"height":279.9};
const content = `<path class="vj4o9achs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:fpt-play" {...props}></Icon>
