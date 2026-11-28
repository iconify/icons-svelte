<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7233x-8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="z7233x-8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:layout-dashboard-bold" {...props}></Icon>
