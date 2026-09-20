<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur9c4g87e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ur9c4g87e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pencil-ruler-solid" {...props}></Icon>
