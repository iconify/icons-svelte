<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgg1uibch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bgg1uibch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:review-request-solid" {...props}></Icon>
