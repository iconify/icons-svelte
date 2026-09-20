<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd9hcq6wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd9hcq6wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-truck" {...props}></Icon>
