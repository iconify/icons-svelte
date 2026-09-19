<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x39s_of4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1472};
const content = `<path class="x39s_of4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:profile" {...props}></Icon>
