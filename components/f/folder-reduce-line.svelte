<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph66lraqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph66lraqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-reduce-line" {...props}></Icon>
