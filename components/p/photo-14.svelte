<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewe08fbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ewe08fbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:photo-14" {...props}></Icon>
