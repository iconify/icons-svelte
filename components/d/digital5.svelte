<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3sbu1bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="q3sbu1bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital5" {...props}></Icon>
