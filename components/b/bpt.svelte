<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leq1pdrbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="leq1pdrbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:bpt" {...props}></Icon>
