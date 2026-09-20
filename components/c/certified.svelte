<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e45jdkbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="e45jdkbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:certified" {...props}></Icon>
