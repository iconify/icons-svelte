<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjbeaebnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sjbeaebnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:remind-outline" {...props}></Icon>
