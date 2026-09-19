<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw64dbbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="aw64dbbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:f04d" {...props}></Icon>
