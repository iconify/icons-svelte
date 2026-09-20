<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zck3w-1kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zck3w-1kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:apple-alt-solid" {...props}></Icon>
