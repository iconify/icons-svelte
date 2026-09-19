<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxa7t1amh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cxa7t1amh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:download" {...props}></Icon>
