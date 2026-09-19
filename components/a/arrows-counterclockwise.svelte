<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-cit1b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y-cit1b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrows-counterclockwise" {...props}></Icon>
