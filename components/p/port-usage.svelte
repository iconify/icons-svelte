<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8gkcej6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p8gkcej6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:port-usage" {...props}></Icon>
