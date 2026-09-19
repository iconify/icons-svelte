<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxn0pcbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vxn0pcbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:loom" {...props}></Icon>
