<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfkl0zb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sfkl0zb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:goblet-full" {...props}></Icon>
