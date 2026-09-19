<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0lj0milb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f0lj0milb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:pied-piper" {...props}></Icon>
