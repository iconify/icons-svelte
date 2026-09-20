<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxafg2elz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sxafg2elz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:obelisk" {...props}></Icon>
