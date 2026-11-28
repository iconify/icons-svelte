<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihyqh-94e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihyqh-94e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:camera-star" {...props}></Icon>
