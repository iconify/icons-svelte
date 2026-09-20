<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxh2dlwch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wxh2dlwch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:power-tower" {...props}></Icon>
