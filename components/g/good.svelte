<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2w8nrbvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y2w8nrbvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:good" {...props}></Icon>
