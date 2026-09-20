<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc0si1p-z.css';
import '../../css/c/ci07z7bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wc0si1p-z"/><path class="ci07z7bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:codescan-checkmark-16" {...props}></Icon>
