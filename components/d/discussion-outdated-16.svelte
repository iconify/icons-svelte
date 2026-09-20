<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dds4u8xcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dds4u8xcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:discussion-outdated-16" {...props}></Icon>
