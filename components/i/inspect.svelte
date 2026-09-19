<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4jgbnbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r4jgbnbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:inspect" {...props}></Icon>
