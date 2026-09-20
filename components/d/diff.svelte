<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy9o_fwfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vy9o_fwfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:diff" {...props}></Icon>
