<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq2dc2dvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sq2dc2dvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:ball-and-socket-joint" {...props}></Icon>
