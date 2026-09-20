<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4d9v6lqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f4d9v6lqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:badge-shield-with-deer-head-with-antlers" {...props}></Icon>
