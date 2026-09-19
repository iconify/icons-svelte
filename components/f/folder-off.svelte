<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0hdih8qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f0hdih8qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder-off" {...props}></Icon>
