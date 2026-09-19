<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag1m98bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ag1m98bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:arrow-up" {...props}></Icon>
