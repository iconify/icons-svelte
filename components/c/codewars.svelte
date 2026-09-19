<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ptetrtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q7ptetrtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:codewars" {...props}></Icon>
