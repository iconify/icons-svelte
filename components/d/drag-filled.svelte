<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuh3r0bvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xuh3r0bvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:drag-filled" {...props}></Icon>
