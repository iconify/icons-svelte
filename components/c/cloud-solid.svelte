<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqfnu818z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uqfnu818z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloud-solid" {...props}></Icon>
