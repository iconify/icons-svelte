<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj7j4ybat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":383,"height":512};
const content = `<path class="nj7j4ybat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jenkins" {...props}></Icon>
