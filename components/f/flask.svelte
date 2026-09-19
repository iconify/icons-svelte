<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv03d2joh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1472,"height":1536};
const content = `<path class="iv03d2joh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:flask" {...props}></Icon>
