<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0ruh7b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0ruh7b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:box" {...props}></Icon>
