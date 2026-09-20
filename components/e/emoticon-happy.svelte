<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akm6_1a0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akm6_1a0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-happy" {...props}></Icon>
