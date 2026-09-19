<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl9l6sb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rl9l6sb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-up-16-solid" {...props}></Icon>
