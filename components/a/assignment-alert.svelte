<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db98s4ozf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="db98s4ozf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:assignment-alert" {...props}></Icon>
