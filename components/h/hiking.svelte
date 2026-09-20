<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8wfjmkdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n8wfjmkdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hiking" {...props}></Icon>
