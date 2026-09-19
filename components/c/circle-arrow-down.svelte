<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m97mmmbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="m97mmmbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:circle-arrow-down" {...props}></Icon>
