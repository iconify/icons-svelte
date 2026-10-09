<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoptugxir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aoptugxir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:circle-dashed-20" {...props}></Icon>
