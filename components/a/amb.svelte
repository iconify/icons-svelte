<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6io6v7ge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q6io6v7ge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:amb" {...props}></Icon>
