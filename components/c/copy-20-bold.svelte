<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd5atu08j.css';
import '../../css/v/veyzdwbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cd5atu08j"/><path class="veyzdwbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:copy-20-bold" {...props}></Icon>
