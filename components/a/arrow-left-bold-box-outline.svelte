<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vksi9_b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vksi9_b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-bold-box-outline" {...props}></Icon>
