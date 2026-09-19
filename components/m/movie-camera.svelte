<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csg07lgga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="csg07lgga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:movie-camera" {...props}></Icon>
