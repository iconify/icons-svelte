<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv4vo1bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wv4vo1bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:book" {...props}></Icon>
