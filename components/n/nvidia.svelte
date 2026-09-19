<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr4df3bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yr4df3bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:nvidia" {...props}></Icon>
