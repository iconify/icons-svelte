<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu_b0rb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1408};
const content = `<path class="zu_b0rb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cloud" {...props}></Icon>
