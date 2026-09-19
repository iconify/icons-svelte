<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyp086bkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uyp086bkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-line-stroke-16" {...props}></Icon>
