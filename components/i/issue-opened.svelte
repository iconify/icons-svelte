<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6f08tbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="g6f08tbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-opened" {...props}></Icon>
