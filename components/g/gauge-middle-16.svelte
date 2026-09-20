<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9lwlibmh.css';
import '../../css/m/mocmm6bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r9lwlibmh"/><path class="mocmm6bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gauge-middle-16" {...props}></Icon>
