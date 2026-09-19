<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flc3sop7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="flc3sop7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:audio-file" {...props}></Icon>
