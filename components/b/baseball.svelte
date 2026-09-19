<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3etuu25j.css';
import '../../css/y/y5pksnbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3etuu25j"/><path class="y5pksnbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:baseball" {...props}></Icon>
