<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t25tctdjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t25tctdjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:book-16" {...props}></Icon>
