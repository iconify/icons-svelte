<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4r-65a1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g4r-65a1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:movie-16" {...props}></Icon>
