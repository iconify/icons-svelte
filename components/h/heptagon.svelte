<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do9zq7gwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do9zq7gwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heptagon" {...props}></Icon>
