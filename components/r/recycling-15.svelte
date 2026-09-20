<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuy5q6b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cuy5q6b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:recycling-15" {...props}></Icon>
