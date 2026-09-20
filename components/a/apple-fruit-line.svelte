<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc35mgb4o.css';
import '../../css/y/y2opnv8ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc35mgb4o"/><path class="y2opnv8ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:apple-fruit-line" {...props}></Icon>
