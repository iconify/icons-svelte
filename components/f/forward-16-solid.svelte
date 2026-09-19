<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfddgduuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rfddgduuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:forward-16-solid" {...props}></Icon>
