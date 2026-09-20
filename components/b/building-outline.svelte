<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1un71jxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i1un71jxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:building-outline" {...props}></Icon>
