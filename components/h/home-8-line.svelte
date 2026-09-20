<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdogm3t6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdogm3t6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-8-line" {...props}></Icon>
