<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8sr93jgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p8sr93jgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:haykal-solid" {...props}></Icon>
