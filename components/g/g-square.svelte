<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3t4odkol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="f3t4odkol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:g-square" {...props}></Icon>
