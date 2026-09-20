<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogo83fbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ogo83fbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:partial" {...props}></Icon>
