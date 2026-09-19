<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab62mr4_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ab62mr4_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-down" {...props}></Icon>
