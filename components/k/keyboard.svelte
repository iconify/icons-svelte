<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-9w4jb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k-9w4jb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:keyboard" {...props}></Icon>
