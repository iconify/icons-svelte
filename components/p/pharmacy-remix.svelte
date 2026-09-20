<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3u148uzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d3u148uzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:pharmacy-remix" {...props}></Icon>
