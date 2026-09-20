<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-33b3hhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="p-33b3hhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:border-top-left" {...props}></Icon>
