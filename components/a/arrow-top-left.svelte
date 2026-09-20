<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/con_4y89t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="con_4y89t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-top-left" {...props}></Icon>
