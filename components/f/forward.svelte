<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuvtw6bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wuvtw6bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:forward" {...props}></Icon>
