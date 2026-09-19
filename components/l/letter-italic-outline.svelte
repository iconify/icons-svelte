<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9oo0hb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9oo0hb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:letter-italic-outline" {...props}></Icon>
