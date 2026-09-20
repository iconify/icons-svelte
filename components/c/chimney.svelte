<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdfuchbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sdfuchbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:chimney" {...props}></Icon>
