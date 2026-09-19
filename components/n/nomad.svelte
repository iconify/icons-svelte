<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjnwaxkty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":438,"height":512};
const content = `<path class="gjnwaxkty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nomad" {...props}></Icon>
