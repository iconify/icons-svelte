<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5j_e6bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d5j_e6bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:download-2" {...props}></Icon>
