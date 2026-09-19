<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0iw-qbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r0iw-qbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cage" {...props}></Icon>
