<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joiq4kbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="joiq4kbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bar-chart-fill-20" {...props}></Icon>
