<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9-3slunj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a9-3slunj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gitlab" {...props}></Icon>
