<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5uke9z4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5uke9z4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:drumstick-solid" {...props}></Icon>
