<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp8e4qb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zp8e4qb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:beam" {...props}></Icon>
