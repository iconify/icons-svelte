<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze0oxb4me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ze0oxb4me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:4-square" {...props}></Icon>
