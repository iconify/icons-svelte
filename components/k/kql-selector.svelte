<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2l0g6bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c2l0g6bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:kql-selector" {...props}></Icon>
