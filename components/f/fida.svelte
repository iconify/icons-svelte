<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1cuu9krx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a1cuu9krx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:fida" {...props}></Icon>
