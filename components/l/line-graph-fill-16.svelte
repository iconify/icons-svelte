<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3lemkowc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u3lemkowc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:line-graph-fill-16" {...props}></Icon>
