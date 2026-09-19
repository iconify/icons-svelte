<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9bnjb9-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="e9bnjb9-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:0-square" {...props}></Icon>
