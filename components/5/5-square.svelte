<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orw-gcrio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="orw-gcrio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:5-square" {...props}></Icon>
