<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pobd2gbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pobd2gbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:hourglass-16" {...props}></Icon>
