<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygsx_6hjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ygsx_6hjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:red-river" {...props}></Icon>
