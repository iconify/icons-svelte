<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cemr4cbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cemr4cbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:briefcase-delete" {...props}></Icon>
