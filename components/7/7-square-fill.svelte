<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5mju5bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a5mju5bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:7-square-fill" {...props}></Icon>
