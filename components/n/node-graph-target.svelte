<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oer3upb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oer3upb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:node-graph-target" {...props}></Icon>
