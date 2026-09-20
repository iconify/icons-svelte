<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfjjnwb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cfjjnwb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:beach" {...props}></Icon>
