<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2g_agbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h2g_agbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:filter-filled" {...props}></Icon>
