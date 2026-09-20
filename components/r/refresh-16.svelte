<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6_e7pqol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x6_e7pqol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:refresh-16" {...props}></Icon>
