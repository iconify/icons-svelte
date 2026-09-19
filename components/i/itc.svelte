<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaawarbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uaawarbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:itc" {...props}></Icon>
