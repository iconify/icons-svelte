<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk6t47z6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yk6t47z6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pause" {...props}></Icon>
