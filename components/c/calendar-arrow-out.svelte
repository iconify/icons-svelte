<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7idm1bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="d7idm1bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-arrow-out" {...props}></Icon>
