<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsujgfxyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xsujgfxyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-up-stroke-16" {...props}></Icon>
