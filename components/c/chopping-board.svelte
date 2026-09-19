<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb-c83bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sb-c83bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:chopping-board" {...props}></Icon>
