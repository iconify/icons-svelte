<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fla4wtbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fla4wtbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:milestone-16" {...props}></Icon>
