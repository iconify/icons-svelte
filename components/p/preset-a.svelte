<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apbnsr93k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="apbnsr93k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:preset-a" {...props}></Icon>
