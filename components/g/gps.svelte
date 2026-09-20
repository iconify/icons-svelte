<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e20m-7bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e20m-7bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gps" {...props}></Icon>
