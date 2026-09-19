<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7oxfibsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":396,"height":512};
const content = `<path class="h7oxfibsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cairo" {...props}></Icon>
