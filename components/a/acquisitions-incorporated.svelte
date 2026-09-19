<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j84lrp6hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="j84lrp6hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:acquisitions-incorporated" {...props}></Icon>
