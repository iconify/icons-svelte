<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3voqrbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="r3voqrbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:linkedin-square" {...props}></Icon>
