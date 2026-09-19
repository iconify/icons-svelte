<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d75j04mlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="d75j04mlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:7-square" {...props}></Icon>
