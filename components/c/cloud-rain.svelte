<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7hm0lwug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7hm0lwug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud-rain" {...props}></Icon>
