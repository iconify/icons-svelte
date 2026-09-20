<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-p2oz0-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i-p2oz0-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:camcorder" {...props}></Icon>
