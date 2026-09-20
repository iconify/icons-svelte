<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbw5l6n7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mbw5l6n7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:plus" {...props}></Icon>
