<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkxpisqwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkxpisqwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:boxing-line" {...props}></Icon>
