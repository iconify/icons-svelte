<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5ophxb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z5ophxb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:rose-solid" {...props}></Icon>
