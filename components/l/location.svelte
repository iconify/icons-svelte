<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3ma3cbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":690,"height":820};
const content = `<path class="k3ma3cbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:location" {...props}></Icon>
