<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3bv6j6bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c3bv6j6bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:line-bar-chart" {...props}></Icon>
