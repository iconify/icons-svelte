<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0xbtfb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0xbtfb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:align-center-outline" {...props}></Icon>
