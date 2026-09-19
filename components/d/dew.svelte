<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb7nz4lfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wb7nz4lfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dew" {...props}></Icon>
