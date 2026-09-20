<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gax5z8n5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gax5z8n5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-down-chevron-circle" {...props}></Icon>
