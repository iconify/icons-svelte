<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-fia57dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d-fia57dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:compress" {...props}></Icon>
