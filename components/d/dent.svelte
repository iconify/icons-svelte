<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp1cw-bvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jp1cw-bvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dent" {...props}></Icon>
