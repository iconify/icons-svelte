<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmma348sl.css';
import '../../css/y/yh9xo0blb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cmma348sl"/><path class="yh9xo0blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-up-right-20-bold" {...props}></Icon>
