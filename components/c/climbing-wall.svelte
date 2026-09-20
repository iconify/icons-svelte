<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ij8m92l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p7ij8m92l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:climbing-wall" {...props}></Icon>
