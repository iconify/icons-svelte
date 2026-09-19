<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oivh0m-4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oivh0m-4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:poll-h" {...props}></Icon>
