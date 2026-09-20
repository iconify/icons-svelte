<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pufh1-b6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pufh1-b6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:dollar" {...props}></Icon>
