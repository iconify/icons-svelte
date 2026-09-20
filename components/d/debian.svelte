<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-2wd-bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c-2wd-bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:debian" {...props}></Icon>
