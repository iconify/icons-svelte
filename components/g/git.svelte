<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v__df4xbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v__df4xbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:git" {...props}></Icon>
