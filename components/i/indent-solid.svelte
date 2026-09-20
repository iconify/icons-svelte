<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhd9nx_yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zhd9nx_yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:indent-solid" {...props}></Icon>
