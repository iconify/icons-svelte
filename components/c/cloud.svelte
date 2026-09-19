<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1amxv-5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o1amxv-5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:cloud" {...props}></Icon>
