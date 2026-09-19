<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl2a4taoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nl2a4taoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:node-graph-node" {...props}></Icon>
