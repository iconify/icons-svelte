<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8y7v2bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":641};
const content = `<path class="l8y7v2bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:resizehorizontal" {...props}></Icon>
