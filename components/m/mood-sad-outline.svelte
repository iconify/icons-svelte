<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1dozmb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s1dozmb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:mood-sad-outline" {...props}></Icon>
