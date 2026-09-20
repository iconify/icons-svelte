<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je1y2wbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="je1y2wbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:charge" {...props}></Icon>
