<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upz_b1bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="upz_b1bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:recycle" {...props}></Icon>
