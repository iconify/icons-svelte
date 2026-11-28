<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydik1iafd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydik1iafd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bag-plus" {...props}></Icon>
