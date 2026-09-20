<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xra29bcgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xra29bcgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:circle-with-dot" {...props}></Icon>
