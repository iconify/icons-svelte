<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bepmzn8hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bepmzn8hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:filter-bypass" {...props}></Icon>
