<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4rxvqb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g4rxvqb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dock" {...props}></Icon>
