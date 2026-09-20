<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj7w4ccsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="nj7w4ccsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:chart-style3" {...props}></Icon>
