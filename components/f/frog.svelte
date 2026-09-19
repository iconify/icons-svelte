<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mejwp-bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mejwp-bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:frog" {...props}></Icon>
