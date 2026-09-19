<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymcb8gbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ymcb8gbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bar-chart-steps" {...props}></Icon>
