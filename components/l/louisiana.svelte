<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0g6_5b-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e0g6_5b-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:louisiana" {...props}></Icon>
