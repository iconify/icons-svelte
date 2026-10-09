<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh390wfyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oh390wfyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-20" {...props}></Icon>
