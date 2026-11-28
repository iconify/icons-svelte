<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcmyc104n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="lcmyc104n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:rock-bold" {...props}></Icon>
