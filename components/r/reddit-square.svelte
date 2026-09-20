<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asprg8bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="asprg8bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:reddit-square" {...props}></Icon>
