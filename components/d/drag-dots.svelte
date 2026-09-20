<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb0oq1bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nb0oq1bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:drag-dots" {...props}></Icon>
