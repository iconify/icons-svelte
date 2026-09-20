<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvt5iabui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tvt5iabui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-down-right-box" {...props}></Icon>
