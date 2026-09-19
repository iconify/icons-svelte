<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9b_vk3fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x9b_vk3fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:duplicate-small" {...props}></Icon>
