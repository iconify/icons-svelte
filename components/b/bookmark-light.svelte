<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybsln6b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybsln6b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bookmark-light" {...props}></Icon>
