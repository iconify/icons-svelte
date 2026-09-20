<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9-3teqfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r9-3teqfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:fold-16" {...props}></Icon>
