<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9qyvcbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m9qyvcbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:qsp" {...props}></Icon>
