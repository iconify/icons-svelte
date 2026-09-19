<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgxld1aoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xgxld1aoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:add-mode" {...props}></Icon>
