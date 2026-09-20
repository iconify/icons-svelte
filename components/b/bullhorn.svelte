<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6l63wbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="f6l63wbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bullhorn" {...props}></Icon>
