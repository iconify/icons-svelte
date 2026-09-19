<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj67mcccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wj67mcccy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:linkedin-stroke-16" {...props}></Icon>
