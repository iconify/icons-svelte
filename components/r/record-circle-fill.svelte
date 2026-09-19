<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvd2vuboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gvd2vuboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:record-circle-fill" {...props}></Icon>
