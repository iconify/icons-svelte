<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0y-h_16m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x0y-h_16m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:palm" {...props}></Icon>
