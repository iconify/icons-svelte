<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_6rajbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g_6rajbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:puzzle-piece" {...props}></Icon>
