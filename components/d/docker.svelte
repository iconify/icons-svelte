<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_0lj959o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w_0lj959o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:docker" {...props}></Icon>
