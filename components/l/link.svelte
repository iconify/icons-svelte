<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbxi97qzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="pbxi97qzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:link" {...props}></Icon>
