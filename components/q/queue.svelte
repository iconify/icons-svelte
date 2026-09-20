<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg7cm0bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hg7cm0bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:queue" {...props}></Icon>
