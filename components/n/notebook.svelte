<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-84n2b3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p-84n2b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:notebook" {...props}></Icon>
