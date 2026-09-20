<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzqxovbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jzqxovbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:entertainment-music" {...props}></Icon>
