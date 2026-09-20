<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7y--t7eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a7y--t7eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:area-chart-filled" {...props}></Icon>
