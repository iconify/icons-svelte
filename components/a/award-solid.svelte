<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfxt7qqpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cfxt7qqpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:award-solid" {...props}></Icon>
