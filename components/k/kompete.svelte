<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5rh4ygbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5rh4ygbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kompete" {...props}></Icon>
