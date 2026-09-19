<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duv8mepcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="duv8mepcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:palette" {...props}></Icon>
