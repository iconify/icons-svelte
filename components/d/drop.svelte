<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0r6-xtig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":610,"height":840};
const content = `<path class="a0r6-xtig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:drop" {...props}></Icon>
