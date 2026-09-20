<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjhk3mbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sjhk3mbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:date-add" {...props}></Icon>
