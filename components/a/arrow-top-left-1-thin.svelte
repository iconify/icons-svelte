<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg1qh8o8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg1qh8o8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-1-thin" {...props}></Icon>
