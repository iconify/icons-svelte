<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whsca8c2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whsca8c2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-down-long-line" {...props}></Icon>
