<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvkad84mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvkad84mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:compass-discover-fill" {...props}></Icon>
