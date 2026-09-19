<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyslfvbtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pyslfvbtj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-bar-graph-fill" {...props}></Icon>
