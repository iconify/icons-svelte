<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9d6xob5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m9d6xob5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:key" {...props}></Icon>
