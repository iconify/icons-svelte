<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaj032vab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zaj032vab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:restaurant-menu" {...props}></Icon>
