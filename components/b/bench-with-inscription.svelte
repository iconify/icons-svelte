<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j386prbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j386prbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bench-with-inscription" {...props}></Icon>
