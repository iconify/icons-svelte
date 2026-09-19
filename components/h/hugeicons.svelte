<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zua73sfyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zua73sfyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hugeicons" {...props}></Icon>
