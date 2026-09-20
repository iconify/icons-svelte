<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbxy78esr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lbxy78esr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:list-unordered-16" {...props}></Icon>
