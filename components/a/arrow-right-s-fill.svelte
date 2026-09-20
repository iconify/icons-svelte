<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5r9be01k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5r9be01k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-s-fill" {...props}></Icon>
