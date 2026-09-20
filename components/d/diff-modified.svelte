<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0emlsjte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="r0emlsjte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-modified" {...props}></Icon>
