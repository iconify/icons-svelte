<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvn7ycb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kvn7ycb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:microsoft-publisher" {...props}></Icon>
