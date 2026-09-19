<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fel8qbbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fel8qbbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:image-flip-horizontal" {...props}></Icon>
