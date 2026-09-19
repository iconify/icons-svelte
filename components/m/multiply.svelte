<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wayyz3edj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1023};
const content = `<path class="wayyz3edj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:multiply" {...props}></Icon>
