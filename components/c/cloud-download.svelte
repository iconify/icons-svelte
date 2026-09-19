<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1alc3bdk.css';
import '../../css/u/uborx5bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j1alc3bdk"/><path class="uborx5bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-download" {...props}></Icon>
