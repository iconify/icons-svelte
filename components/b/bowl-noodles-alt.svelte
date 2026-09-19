<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq4vo4zge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq4vo4zge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bowl-noodles-alt" {...props}></Icon>
